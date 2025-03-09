# Function: <code>dst_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586330512,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:402",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586526784,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:402",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586910592,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:402",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587051984,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:402",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587179328,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:402",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586330512,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586526784,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586910592,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587051984,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587179328,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586763248,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586969552,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587356880,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587501168,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587633344,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586763248,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071586969552,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587356880,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587501168,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587633344,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586949824,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587164448,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587559760,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587705552,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587838000,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:411",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586949824,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587164448,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587559760,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587705552,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587838000,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587075520,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:414",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587295744,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:414",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587706208,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:414",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587855520,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:414",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587995136,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:414",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587075520,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587295744,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587706208,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587855520,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587995136,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587577040,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:403",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587817568,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:403",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588232928,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:403",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588384800,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:403",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588531584,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:403",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587577040,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071587817568,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588232928,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588384800,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588531584,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587886160,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588160752,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588587200,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588743104,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588896208,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587886160,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588160752,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588587200,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588743104,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588896208,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588027920,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588344720,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588792080,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588963312,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589119712,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:387",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588027920,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588344720,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588792080,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588963312,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589119712,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588341072,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588745120,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589223472,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589407248,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589573088,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588341072,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588745120,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589223472,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589407248,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589573088,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588547472,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588968864,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589448736,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589631488,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589797472,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588547472,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588968864,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589448736,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589631488,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589797472,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589398320,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589923984,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590437120,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590641744,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590819680,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589398320,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589923984,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590437120,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590641744,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590819680,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589399424,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589964528,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590496384,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590701808,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590879728,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:378",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589399424,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589964528,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590496384,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590701808,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590879728,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589296624,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:381",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589879424,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:381",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590422016,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:381",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590627616,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:381",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590808864,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:381",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589296624,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589879424,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590422016,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590627616,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071590808864,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590024672,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:383",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590643328,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:383",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591219744,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:383",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591440960,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:383",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591627232,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:383",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590024672,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071590643328,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591219744,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591440960,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071591627232,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591565712,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592268048,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071592882560,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593120128,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071593320848,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591565712,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071592268048,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071592882560,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071593120128,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071593320848,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593343952,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:377",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594103248,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:377",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594761696,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:377",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595016352,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:377",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595226096,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:377",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593343952,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071594103248,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071594761696,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595016352,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595226096,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593806224,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:391",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071594490096,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:391",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595154096,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:391",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595409872,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:391",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595622224,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:391",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593806224,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071594490096,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595154096,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595409872,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595622224,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594587632,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595292928,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071595996256,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596251568,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071596469472,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:384",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594587632,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071595292928,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071595996256,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071596251568,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071596469472,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502085000,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336502571608,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503104480,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503314992,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336503502888,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502085000,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446603336502571608,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446603336503104480,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446603336503314992,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446603336503502888,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234834840,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235278556,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235786152,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3235981840,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3236154712,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234834840,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 3235278556,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3235786152,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3235981840,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 3236154712,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295537648,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296157600,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055296817984,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297071376,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055297293152,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295537648,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 13835058055296157600,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055296817984,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055297071376,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 13835058055297293152,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278358922,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936278730200,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279156434,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279329502,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936279475372,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278730200,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936279156434,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936279329502,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936279475372,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446743936278358922,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588154208,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588575248,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589053104,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589235856,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589401840,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154208,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588575248,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589053104,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589235856,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589401840,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate ❓</summary>

```c
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587867040,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588287232,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588778144,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588960848,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589126832,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587867040,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071588287232,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588778144,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071588960848,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589126832,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate ❓</summary>

```c
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588486032,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589011424,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589489968,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589672720,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589838704,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588486032,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589011424,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589489968,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589672720,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589838704,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
int dst_discard(struct sk_buff * skb)
```

```json
{
  "name": "dst_discard",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588622944,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/core/dst.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589050016,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv4/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589536608,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/xfrm/xfrm_policy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589721856,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/route.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589889984,
      "name": "dst_discard",
      "external": false,
      "loc": "include/net/dst.h:379",
      "file": "net/ipv6/exthdrs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622944,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 13
    },
    {
      "addr": 18446744071589050016,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589536608,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589721856,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071589889984,
      "name": "dst_discard",
      "section": ".text",
      "bind": "STB_LOCAL",
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
