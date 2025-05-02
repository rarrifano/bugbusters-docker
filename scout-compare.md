
## Overview

| Image reference | `zabbix/zabbix-web-nginx-pgsql:ubuntu-6.0-latest`        | `zabbix/zabbix-web-nginx-pgsql:alpine-6.0-latest`        |
|-----------------|---------------------------|---------------------------|
| - digest        | `662bd6eb0a86` | `ea95218af993` |
| - tag           | `ubuntu-6.0-latest` | `alpine-6.0-latest` |
| - provenance | https://github.com/zabbix/zabbix-docker/commit/4d70062ef4fdc3088bafb8bee1953ccdf8fcfb58 | https://git.zabbix.com/scm/zbx/zabbix.git/commit/4d70062ef4fdc3088bafb8bee1953ccdf8fcfb58 |
| - vulnerabilities | <img alt="critical: 0" src="https://img.shields.io/badge/critical-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/high-0-lightgrey"/> <img alt="medium: 13" src="https://img.shields.io/badge/medium-13-fbb552"/> <img alt="low: 9" src="https://img.shields.io/badge/low-9-fce1a9"/> <!-- unspecified: 0 --> | <img alt="critical: 0" src="https://img.shields.io/badge/critical-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/high-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/medium-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/low-0-lightgrey"/> <!-- unspecified: 0 --> |
| - platform | linux/amd64 | linux/amd64 |
| - size | 149 MB | 81 MB (-68 MB) |
| - packages | 209 | 140 (-69) |
| **Base Image** | `ubuntu:noble`<br/>also known as:<br/>• <code>24.04</code><br/>• <code>latest</code> | `alpine:3`<br/>also known as:<br/>• <code>3.21</code><br/>• <code>3.21.3</code><br/>• <code>latest</code> |
| - vulnerabilities | <img alt="critical: 0" src="https://img.shields.io/badge/critical-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/high-0-lightgrey"/> <img alt="medium: 3" src="https://img.shields.io/badge/medium-3-fbb552"/> <img alt="low: 6" src="https://img.shields.io/badge/low-6-fce1a9"/> <!-- unspecified: 0 --> | <img alt="critical: 0" src="https://img.shields.io/badge/critical-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/high-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/medium-0-lightgrey"/> <img alt="low: 0" src="https://img.shields.io/badge/low-0-lightgrey"/> <!-- unspecified: 0 --> |



<details><summary><strong>Labels</strong> (2 changes)</summary>

> * `-` 1 removed
> * `±` 1 changed
> * _10 unchanged_


```diff
 org.opencontainers.image.authors=Alexey Pustovalov <alexey.pustovalov@zabbix.com>
-org.opencontainers.image.created=2025-04-22T14:26:28.500Z
+org.opencontainers.image.created=2025-04-22T15:08:27.363Z
 org.opencontainers.image.description=Zabbix web-interface based on Nginx web server with PostgreSQL database support
 org.opencontainers.image.documentation=https://www.zabbix.com/documentation/6.0/manual/installation/containers
 org.opencontainers.image.licenses=GPL v2.0
-org.opencontainers.image.ref.name=ubuntu
 org.opencontainers.image.revision=4d70062ef4fdc3088bafb8bee1953ccdf8fcfb58
 org.opencontainers.image.source=https://git.zabbix.com/scm/zbx/zabbix.git
 org.opencontainers.image.title=Zabbix web-interface (Nginx, PostgreSQL)
 org.opencontainers.image.url=https://zabbix.com/
 org.opencontainers.image.vendor=Zabbix SIA
 org.opencontainers.image.version=6.0.40
```


</details>



<details><summary><strong>Packages and Vulnerabilities</strong> (337 package changes and 22 vulnerability changes)</summary>

> * :heavy_plus_sign: 134 packages added
> * :heavy_minus_sign: 203 packages removed
> * 6 packages unchanged


> * :heavy_check_mark: 22 vulnerabilities removed
<details><summary>Changes for packages of type <code>apk</code> (131 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>zabbix/zabbix-web-nginx-pgsql:ubuntu-6.0-latest</code></th>
		<th valign="top">Version<br/><code>zabbix/zabbix-web-nginx-pgsql:alpine-6.0-latest</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>acl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.2-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>acl-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.2-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-base</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.21.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-baselayout</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.6.8-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-baselayout-data</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.6.8-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-keys</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.5-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>alpine-release</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.21.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>aom</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.11.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>aom-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.11.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>apache2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.4.62-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>apache2-ssl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.4.62-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>apk-tools</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.14.6-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>apr</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.7.5-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>apr-util</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.6.3-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>argon2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20190702-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>argon2-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20190702-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>bash</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>5.2.37-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>brotli</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.0-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>brotli-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.0-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>busybox</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.37.0-r12</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>busybox-binsh</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.37.0-r12</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>bzip2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.0.8-r6</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>c-ares</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.34.5-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ca-certificates</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20241121-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ca-certificates-bundle</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20241121-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>curl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.12.1-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>cyrus-sasl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.1.28-r8</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>dav1d</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.5.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>expat</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.7.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>freetype</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.13.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>gcc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>14.2.0-r4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>gdbm</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.24-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>gettext</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.22.5-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libavif</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.0.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libbsd</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.12.2-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libbz2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.0.8-r6</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libcrypto3</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.3.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libcurl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.12.1-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libdav1d</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.5.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libedit</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>20240808.3.1-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libexpat</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.7.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libffi</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.4.7-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libgcc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>14.2.0-r4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libice</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.1-r6</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libidn2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.3.7-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libintl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.22.5-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libjpeg-turbo</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.0.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libldap</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.6.8-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libmd</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libncursesw</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>6.5_p20241006-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libpanelw</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>6.5_p20241006-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libpng</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.6.47-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libpq</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>17.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libpsl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>0.21.5-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libsasl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.1.28-r8</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libsharpyuv</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.4.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libsm</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.4-r4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libssl3</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.3.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libstdc++</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>14.2.0-r4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libunistring</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libuuid</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.40.4-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libwebp</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.4.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libx11</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.8.10-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxau</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.0.11-r4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxcb</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.16.1-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxdmcp</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.1.5-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxext</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.6-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxml2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.13.4-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxpm</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.5.17-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>libxt</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.1-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>lz4</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.10.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>lz4-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.10.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>mpdecimal</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>4.0.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>musl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.5-r9</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>musl-utils</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2.5-r9</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ncurses</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>6.5_p20241006-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ncurses-terminfo-base</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>6.5_p20241006-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>nghttp2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.64.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>nghttp2-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.64.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>nginx</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.26.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>oniguruma</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>6.9.9-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>openldap</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.6.8-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>openssl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.3.3-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>pax-utils</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.8-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>pcre</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.45-r3</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>pcre2</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>10.43-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-bcmath</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-common</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-ctype</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-dom</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-fileinfo</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-fpm</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-gd</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-gettext</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-ldap</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-mbstring</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-openssl</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-pgsql</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-session</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-simplexml</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-sockets</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-xmlreader</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>php83-xmlwriter</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.3.19-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>postgresql-common</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.2-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>postgresql17</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>17.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>postgresql17-client</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>17.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>py3-packaging</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>24.2-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>py3-packaging-pyc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>24.2-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>py3-parsing</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>py3-parsing-pyc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.4-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>py3-setuptools</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>70.3.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>py3-setuptools-pyc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>70.3.0-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>pyc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.12.10-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>python3</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.12.10-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>python3-pyc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.12.10-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>python3-pycache-pyc0</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.12.10-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>readline</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>8.2.13-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>scanelf</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.8-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>sqlite</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.48.0-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>sqlite-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.48.0-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>ssl_client</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.37.0-r12</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>supervisor</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>4.2.5-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>supervisor-pyc</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>4.2.5-r5</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>tzdata</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2025b-r0</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>util-linux</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>2.40.4-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>xz</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>5.6.3-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>xz-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>5.6.3-r1</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>zlib</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.3.1-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>zstd</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.5.6-r2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>zstd-libs</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>1.5.6-r2</code></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>deb</code> (203 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>zabbix/zabbix-web-nginx-pgsql:ubuntu-6.0-latest</code></th>
		<th valign="top">Version<br/><code>zabbix/zabbix-web-nginx-pgsql:alpine-6.0-latest</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>apt</strong></td>
		<td valign="top"><code>2.7.14build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>base-files</strong></td>
		<td valign="top"><code>13ubuntu10.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>base-passwd</strong></td>
		<td valign="top"><code>3.6.3build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>bash</strong></td>
		<td valign="top"><code>5.2.21-2ubuntu4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>bsdutils</strong></td>
		<td valign="top"><code>1:2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ca-certificates</strong></td>
		<td valign="top"><code>20240203</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>coreutils</strong></td>
		<td valign="top"><code>9.4-3ubuntu6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2016--2781" src="https://img.shields.io/badge/CVE--2016--2781-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>curl</strong></td>
		<td valign="top"><code>8.5.0-2ubuntu10.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dash</strong></td>
		<td valign="top"><code>0.5.12-6ubuntu5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>debconf</strong></td>
		<td valign="top"><code>1.5.86ubuntu1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>debianutils</strong></td>
		<td valign="top"><code>5.17build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>diffutils</strong></td>
		<td valign="top"><code>1:3.10-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>dpkg</strong></td>
		<td valign="top"><code>1.22.6ubuntu6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>e2fsprogs</strong></td>
		<td valign="top"><code>1.47.0-2.4~exp1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>findutils</strong></td>
		<td valign="top"><code>4.9.0-5build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fontconfig-config</strong></td>
		<td valign="top"><code>2.15.0-1.1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fonts-dejavu-core</strong></td>
		<td valign="top"><code>2.37-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>fonts-dejavu-mono</strong></td>
		<td valign="top"><code>2.37-8</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gcc-14-base</strong></td>
		<td valign="top"><code>14.2.0-4ubuntu2~24.04</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gpgv</strong></td>
		<td valign="top"><code>2.4.4-2ubuntu17.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2022--3219" src="https://img.shields.io/badge/CVE--2022--3219-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>grep</strong></td>
		<td valign="top"><code>3.11-4build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>gzip</strong></td>
		<td valign="top"><code>1.12-1ubuntu3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>hostname</strong></td>
		<td valign="top"><code>3.23+nmu2ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>init-system-helpers</strong></td>
		<td valign="top"><code>1.66ubuntu1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>iproute2</strong></td>
		<td valign="top"><code>6.1.0-1ubuntu6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libacl1</strong></td>
		<td valign="top"><code>2.3.2-1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaom3</strong></td>
		<td valign="top"><code>3.8.2-2ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libapparmor1</strong></td>
		<td valign="top"><code>4.0.1really4.0.1-0ubuntu0.24.04.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libapt-pkg6.0t64</strong></td>
		<td valign="top"><code>2.7.14build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libargon2-1</strong></td>
		<td valign="top"><code>0~20190702+dfsg-4build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libassuan0</strong></td>
		<td valign="top"><code>2.5.6-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libattr1</strong></td>
		<td valign="top"><code>1:2.5.2-1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaudit-common</strong></td>
		<td valign="top"><code>1:3.1.2-2.1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libaudit1</strong></td>
		<td valign="top"><code>1:3.1.2-2.1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libblkid1</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbpf1</strong></td>
		<td valign="top"><code>1:1.3.0-2build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2025--29481" src="https://img.shields.io/badge/CVE--2025--29481-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbrotli1</strong></td>
		<td valign="top"><code>1.1.0-2build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbsd0</strong></td>
		<td valign="top"><code>0.12.1-1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libbz2-1.0</strong></td>
		<td valign="top"><code>1.0.8-5.1build0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libc-bin</strong></td>
		<td valign="top"><code>2.39-0ubuntu8.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libc6</strong></td>
		<td valign="top"><code>2.39-0ubuntu8.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcap-ng0</strong></td>
		<td valign="top"><code>0.8.4-2build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcap2</strong></td>
		<td valign="top"><code>1:2.66-5ubuntu2.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcap2-bin</strong></td>
		<td valign="top"><code>1:2.66-5ubuntu2.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcom-err2</strong></td>
		<td valign="top"><code>1.47.0-2.4~exp1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcrypt1</strong></td>
		<td valign="top"><code>1:4.4.36-4build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcryptsetup12</strong></td>
		<td valign="top"><code>2:2.7.0-1ubuntu4.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libcurl4t64</strong></td>
		<td valign="top"><code>8.5.0-2ubuntu10.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2025--0167" src="https://img.shields.io/badge/CVE--2025--0167-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdb5.3t64</strong></td>
		<td valign="top"><code>5.3.28+dfsg2-7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libde265-0</strong></td>
		<td valign="top"><code>1.0.15-1build3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="medium : CVE--2024--38950" src="https://img.shields.io/badge/CVE--2024--38950-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2024--38949" src="https://img.shields.io/badge/CVE--2024--38949-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdebconfclient0</strong></td>
		<td valign="top"><code>0.271ubuntu3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdeflate0</strong></td>
		<td valign="top"><code>1.19-1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libdevmapper1.02.1</strong></td>
		<td valign="top"><code>2:1.02.185-3ubuntu3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libedit2</strong></td>
		<td valign="top"><code>3.1-20230828-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libelf1t64</strong></td>
		<td valign="top"><code>0.190-1.1ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="medium : CVE--2025--1352" src="https://img.shields.io/badge/CVE--2025--1352-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2025--1376" src="https://img.shields.io/badge/CVE--2025--1376-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libexpat1</strong></td>
		<td valign="top"><code>2.6.1-2ubuntu0.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libext2fs2t64</strong></td>
		<td valign="top"><code>1.47.0-2.4~exp1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfdisk1</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libffi8</strong></td>
		<td valign="top"><code>3.4.6-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfontconfig1</strong></td>
		<td valign="top"><code>2.15.0-1.1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libfreetype6</strong></td>
		<td valign="top"><code>2.13.2+dfsg-1build3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgcc-s1</strong></td>
		<td valign="top"><code>14.2.0-4ubuntu2~24.04</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgcrypt20</strong></td>
		<td valign="top"><code>1.10.3-2build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2024--2236" src="https://img.shields.io/badge/CVE--2024--2236-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgd3</strong></td>
		<td valign="top"><code>2.3.3-9ubuntu5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdbm-compat4t64</strong></td>
		<td valign="top"><code>1.23-5.1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgdbm6t64</strong></td>
		<td valign="top"><code>1.23-5.1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgmp10</strong></td>
		<td valign="top"><code>2:6.3.0+dfsg-2ubuntu6.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgnutls30t64</strong></td>
		<td valign="top"><code>3.8.3-1.1ubuntu3.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgpg-error0</strong></td>
		<td valign="top"><code>1.47-3build2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libgssapi-krb5-2</strong></td>
		<td valign="top"><code>1.20.1-6ubuntu2.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libheif-plugin-aomdec</strong></td>
		<td valign="top"><code>1.17.6-1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libheif-plugin-libde265</strong></td>
		<td valign="top"><code>1.17.6-1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libheif1</strong></td>
		<td valign="top"><code>1.17.6-1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libhogweed6t64</strong></td>
		<td valign="top"><code>3.9.1-2.2build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libicu74</strong></td>
		<td valign="top"><code>74.2-1ubuntu3.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libidn2-0</strong></td>
		<td valign="top"><code>2.3.7-2build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjbig0</strong></td>
		<td valign="top"><code>2.1-6.1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjpeg-turbo8</strong></td>
		<td valign="top"><code>2.1.5-2ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjpeg8</strong></td>
		<td valign="top"><code>8c-2ubuntu11</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libjson-c5</strong></td>
		<td valign="top"><code>0.17-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libk5crypto3</strong></td>
		<td valign="top"><code>1.20.1-6ubuntu2.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkeyutils1</strong></td>
		<td valign="top"><code>1.6.3-3build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkmod2</strong></td>
		<td valign="top"><code>31+20240202-2ubuntu7.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkrb5-3</strong></td>
		<td valign="top"><code>1.20.1-6ubuntu2.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libkrb5support0</strong></td>
		<td valign="top"><code>1.20.1-6ubuntu2.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2025--3576" src="https://img.shields.io/badge/CVE--2025--3576-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libldap-common</strong></td>
		<td valign="top"><code>2.6.7+dfsg-1~exp1ubuntu8.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libldap2</strong></td>
		<td valign="top"><code>2.6.7+dfsg-1~exp1ubuntu8.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblerc4</strong></td>
		<td valign="top"><code>4.0.0+ds-4ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblz4-1</strong></td>
		<td valign="top"><code>1.9.4-1build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>liblzma5</strong></td>
		<td valign="top"><code>5.6.1+really5.4.5-1ubuntu0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmd0</strong></td>
		<td valign="top"><code>1.1.0-2build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmnl0</strong></td>
		<td valign="top"><code>1.0.5-2build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libmount1</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libncursesw6</strong></td>
		<td valign="top"><code>6.4+20240113-1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnettle8t64</strong></td>
		<td valign="top"><code>3.9.1-2.2build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnghttp2-14</strong></td>
		<td valign="top"><code>1.59.0-1ubuntu0.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libnpth0t64</strong></td>
		<td valign="top"><code>1.6-3.1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libonig5</strong></td>
		<td valign="top"><code>6.9.9-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libp11-kit0</strong></td>
		<td valign="top"><code>0.25.3-4ubuntu2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam-modules</strong></td>
		<td valign="top"><code>1.5.3-5ubuntu5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam-modules-bin</strong></td>
		<td valign="top"><code>1.5.3-5ubuntu5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam-runtime</strong></td>
		<td valign="top"><code>1.5.3-5ubuntu5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpam0g</strong></td>
		<td valign="top"><code>1.5.3-5ubuntu5.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="medium : CVE--2024--10963" src="https://img.shields.io/badge/CVE--2024--10963-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2024--10041" src="https://img.shields.io/badge/CVE--2024--10041-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpcre2-8-0</strong></td>
		<td valign="top"><code>10.42-4ubuntu2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libperl5.38t64</strong></td>
		<td valign="top"><code>5.38.2-3.2ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpng16-16t64</strong></td>
		<td valign="top"><code>1.6.43-5build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2022--3857" src="https://img.shields.io/badge/CVE--2022--3857-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpq5</strong></td>
		<td valign="top"><code>16.8-0ubuntu0.24.04.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libproc2-0</strong></td>
		<td valign="top"><code>2:4.0.4-4ubuntu3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpsl5t64</strong></td>
		<td valign="top"><code>0.21.2-1.1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpython3-stdlib</strong></td>
		<td valign="top"><code>3.12.3-0ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpython3.12-minimal</strong></td>
		<td valign="top"><code>3.12.3-1ubuntu0.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libpython3.12-stdlib</strong></td>
		<td valign="top"><code>3.12.3-1ubuntu0.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libreadline8t64</strong></td>
		<td valign="top"><code>8.2-4build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>librtmp1</strong></td>
		<td valign="top"><code>2.4+20151223.gitfa8646d.1-2build7</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsasl2-2</strong></td>
		<td valign="top"><code>2.1.28+dfsg1-5ubuntu3.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsasl2-modules-db</strong></td>
		<td valign="top"><code>2.1.28+dfsg1-5ubuntu3.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libseccomp2</strong></td>
		<td valign="top"><code>2.5.5-1ubuntu3.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libselinux1</strong></td>
		<td valign="top"><code>3.5-2ubuntu2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsemanage-common</strong></td>
		<td valign="top"><code>3.5-1build5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsemanage2</strong></td>
		<td valign="top"><code>3.5-1build5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsepol2</strong></td>
		<td valign="top"><code>3.5-2build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsharpyuv0</strong></td>
		<td valign="top"><code>1.3.2-0.4build3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsmartcols1</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsodium23</strong></td>
		<td valign="top"><code>1.0.18-1build3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsqlite3-0</strong></td>
		<td valign="top"><code>3.45.1-1ubuntu2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="medium : CVE--2025--3277" src="https://img.shields.io/badge/CVE--2025--3277-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2025--29087" src="https://img.shields.io/badge/CVE--2025--29087-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libss2</strong></td>
		<td valign="top"><code>1.47.0-2.4~exp1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libssh-4</strong></td>
		<td valign="top"><code>0.10.6-2build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libssl3t64</strong></td>
		<td valign="top"><code>3.0.13-0ubuntu3.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libstdc++6</strong></td>
		<td valign="top"><code>14.2.0-4ubuntu2~24.04</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsystemd-shared</strong></td>
		<td valign="top"><code>255.4-1ubuntu8.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libsystemd0</strong></td>
		<td valign="top"><code>255.4-1ubuntu8.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtasn1-6</strong></td>
		<td valign="top"><code>4.19.0-3ubuntu0.24.04.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtiff6</strong></td>
		<td valign="top"><code>4.5.1+git230720-4ubuntu2.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2024--6716" src="https://img.shields.io/badge/CVE--2024--6716-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtinfo6</strong></td>
		<td valign="top"><code>6.4+20240113-1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtirpc-common</strong></td>
		<td valign="top"><code>1.3.4+ds-1.1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libtirpc3t64</strong></td>
		<td valign="top"><code>1.3.4+ds-1.1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libudev1</strong></td>
		<td valign="top"><code>255.4-1ubuntu8.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libunistring5</strong></td>
		<td valign="top"><code>1.1-2build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libuuid1</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libwebp7</strong></td>
		<td valign="top"><code>1.3.2-0.4build3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx11-6</strong></td>
		<td valign="top"><code>2:1.8.7-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libx11-data</strong></td>
		<td valign="top"><code>2:1.8.7-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxau6</strong></td>
		<td valign="top"><code>1:1.0.9-1build6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxcb1</strong></td>
		<td valign="top"><code>1.15-1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxdmcp6</strong></td>
		<td valign="top"><code>1:1.1.3-0ubuntu6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxml2</strong></td>
		<td valign="top"><code>2.9.14+dfsg-1.3ubuntu3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 2" src="https://img.shields.io/badge/M-2-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (2):</strong><br/><ul><li><img alt="medium : CVE--2025--32415" src="https://img.shields.io/badge/CVE--2025--32415-lightgrey?label=medium%20&labelColor=fbb552"/></li><li><img alt="medium : CVE--2025--32414" src="https://img.shields.io/badge/CVE--2025--32414-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxpm4</strong></td>
		<td valign="top"><code>1:3.5.17-1build2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxslt1.1</strong></td>
		<td valign="top"><code>1.1.39-0exp1ubuntu0.24.04.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxtables12</strong></td>
		<td valign="top"><code>1.8.10-3ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libxxhash0</strong></td>
		<td valign="top"><code>0.8.2-2build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>libzstd1</strong></td>
		<td valign="top"><code>1.5.5+dfsg2-2build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>locales</strong></td>
		<td valign="top"><code>2.39-0ubuntu8.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2016--20013" src="https://img.shields.io/badge/CVE--2016--20013-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>login</strong></td>
		<td valign="top"><code>1:4.13+dfsg1-4ubuntu3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>logsave</strong></td>
		<td valign="top"><code>1.47.0-2.4~exp1ubuntu4.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mawk</strong></td>
		<td valign="top"><code>1.3.4.20240123-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>media-types</strong></td>
		<td valign="top"><code>10.1.0</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>mount</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ncurses-base</strong></td>
		<td valign="top"><code>6.4+20240113-1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ncurses-bin</strong></td>
		<td valign="top"><code>6.4+20240113-1ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>netbase</strong></td>
		<td valign="top"><code>6.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>nginx</strong></td>
		<td valign="top"><code>1.24.0-2ubuntu7.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 1" src="https://img.shields.io/badge/M-1-fbb552"/> <img alt="low: 0" src="https://img.shields.io/badge/L-0-lightgrey"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="medium : CVE--2025--23419" src="https://img.shields.io/badge/CVE--2025--23419-lightgrey?label=medium%20&labelColor=fbb552"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>nginx-common</strong></td>
		<td valign="top"><code>1.24.0-2ubuntu7.3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>openssl</strong></td>
		<td valign="top"><code>3.0.13-0ubuntu3.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2024--41996" src="https://img.shields.io/badge/CVE--2024--41996-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>passwd</strong></td>
		<td valign="top"><code>1:4.13+dfsg1-4ubuntu3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td colspan="2"></td>
		<td valign="top"><img alt="critical: 0" src="https://img.shields.io/badge/C-0-lightgrey"/> <img alt="high: 0" src="https://img.shields.io/badge/H-0-lightgrey"/> <img alt="medium: 0" src="https://img.shields.io/badge/M-0-lightgrey"/> <img alt="low: 1" src="https://img.shields.io/badge/L-1-fce1a9"/> <!-- unspecified: 0 --></td>
		<td valign="top"></td>
	</tr><tr>
		<td colspan="2"></td>
		<td valign="top"><strong>Removed vulnerabilities (1):</strong><br/><ul><li><img alt="low : CVE--2024--56433" src="https://img.shields.io/badge/CVE--2024--56433-lightgrey?label=low%20&labelColor=fce1a9"/></li></ul></td>
		<td valign="top"></td>
	</tr><tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>perl</strong></td>
		<td valign="top"><code>5.38.2-3.2ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>perl-base</strong></td>
		<td valign="top"><code>5.38.2-3.2ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>perl-modules-5.38</strong></td>
		<td valign="top"><code>5.38.2-3.2ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php-common</strong></td>
		<td valign="top"><code>2:93ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-bcmath</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-cli</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-common</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-fpm</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-gd</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-ldap</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-mbstring</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-opcache</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-pgsql</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-readline</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>php8.3-xml</strong></td>
		<td valign="top"><code>8.3.6-0ubuntu0.24.04.4</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>postgresql-client</strong></td>
		<td valign="top"><code>16+257build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>postgresql-client-16</strong></td>
		<td valign="top"><code>16.8-0ubuntu0.24.04.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>postgresql-client-common</strong></td>
		<td valign="top"><code>257build1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>procps</strong></td>
		<td valign="top"><code>2:4.0.4-4ubuntu3.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>psmisc</strong></td>
		<td valign="top"><code>23.7-1build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3</strong></td>
		<td valign="top"><code>3.12.3-0ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-minimal</strong></td>
		<td valign="top"><code>3.12.3-0ubuntu2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3-pkg-resources</strong></td>
		<td valign="top"><code>68.1.2-2ubuntu1.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3.12</strong></td>
		<td valign="top"><code>3.12.3-1ubuntu0.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>python3.12-minimal</strong></td>
		<td valign="top"><code>3.12.3-1ubuntu0.5</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>readline-common</strong></td>
		<td valign="top"><code>8.2-4build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sed</strong></td>
		<td valign="top"><code>4.9-2build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sensible-utils</strong></td>
		<td valign="top"><code>0.0.22</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>supervisor</strong></td>
		<td valign="top"><code>4.2.5-1ubuntu0.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>systemd</strong></td>
		<td valign="top"><code>255.4-1ubuntu8.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>systemd-dev</strong></td>
		<td valign="top"><code>255.4-1ubuntu8.6</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>sysvinit-utils</strong></td>
		<td valign="top"><code>3.08-6ubuntu3</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>tar</strong></td>
		<td valign="top"><code>1.35+dfsg-3build1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>tzdata</strong></td>
		<td valign="top"><code>2025b-0ubuntu0.24.04</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ubuntu-keyring</strong></td>
		<td valign="top"><code>2023.11.28.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>ucf</strong></td>
		<td valign="top"><code>3.0043+nmu1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>unminimize</strong></td>
		<td valign="top"><code>0.2.1</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>util-linux</strong></td>
		<td valign="top"><code>2.39.3-9ubuntu6.2</code></td>
		<td valign="top"></td>
	</tr>
	<tr>
		<td valign="top">:heavy_minus_sign:</td>
		<td valign="top"><strong>zlib1g</strong></td>
		<td valign="top"><code>1:1.3.dfsg-3.1ubuntu2.1</code></td>
		<td valign="top"></td>
	</tr>
	
</table>
</details>
<details><summary>Changes for packages of type <code>pypi</code> (3 changes)</summary>
<table>
	<tr>
		<th></th>
		<th valign="top">Package</th>
		<th valign="top">Version<br/><code>zabbix/zabbix-web-nginx-pgsql:ubuntu-6.0-latest</code></th>
		<th valign="top">Version<br/><code>zabbix/zabbix-web-nginx-pgsql:alpine-6.0-latest</code></th>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>packaging</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>24.2</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>pyparsing</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>3.1.4</code></td>
	</tr>
	<tr>
		<td valign="top">:heavy_plus_sign:</td>
		<td valign="top"><strong>setuptools</strong></td>
		<td valign="top"></td>
		<td valign="top"><code>70.3.0</code></td>
	</tr>
	
</table>
</details>
</details>

