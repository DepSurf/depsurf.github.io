# Struct: <code>xfrm_dst</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct flow_cache_object flo;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct flow_cache_object flo;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct flow_cache_object flo;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct flow_cache_object flo;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
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
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
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
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct xfrm_dst {
    union (anon) u;
    struct dst_entry * route;
    struct dst_entry * child;
    struct dst_entry * path;
    struct xfrm_policy *[2] pols;
    int num_pols;
    int num_xfrms;
    u32 xfrm_genid;
    u32 policy_genid;
    u32 route_mtu_cached;
    u32 child_mtu_cached;
    u32 route_cookie;
    u32 path_cookie;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct flow_cache_object flo</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct dst_entry * child</code>
</li>
<li>
<b>Field added. </b>
<code>struct dst_entry * path</code>
</li>
</ul>
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
