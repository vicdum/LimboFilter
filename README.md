<img src="https://elytrium.net/src/img/elytrium.webp" alt="Elytrium" align="right">

# LimboFilter 

[![Join our Discord](https://img.shields.io/discord/775778822334709780.svg?logo=discord&label=Discord)](https://ely.su/discord)
![Modrinth Game Versions](https://img.shields.io/modrinth/game-versions/6zIy0zBK?logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAIkAAAA8CAMAAABl%2FWk9AAABAlBMVEUAAAAApcwAqM4Apc4Ap88Apc4Apc4AqM0Aps0Ap84Apc0ApswApc4Aps0Ap80Aps4Ap80Aps0Ap84Aps0Aps4Aps0EqdAHrNMKrtQNsdcRtNoVttwWtt0buuAbuuAbuuAauuAbuuEauuAbu%2BAbuuAbuuEbu%2BAbuuEau%2BAbuuAbuuEau%2BEauuAbuuAbueAbuuAau%2BEbuuAauuAauuAbuuEauuEau%2BAbuuAau%2BEbu%2BAWtt0bvOAau%2BEZuOEYt94cvOEUtt8YudsVsdYAn90A%2F%2F8CqM8Ap84Bp84Aps0Ap80Aps0Aps0Aps0auuAauuAbuuAbuuAauuAauuAbuuAAps0buuCTPBtaAAAAVHRSTlMAIhwzOj5ESk1aZnB3f4iTnKWqrrW7xMDCxdDa3%2BDc2tbMxcC8uLOvp6KflpCHgXl1b15ZVE5EQDovKSQhHRcRDAgFAgHL1Nne5e30%2FPj08e3q5vwu6%2BLEAAADTUlEQVR42sXXhXLDPAzAcY2ZGcrMzAzjYhK9%2F6N8YA8zW62Xwu9gvOp6yt8JTKmSjXnHA18Jlqn63xAj5IbLGqWWi%2FvH%2BJ2jufwh3oUXPYSGMmlYjFLcN0aRkc%2BJzKACi5DUUSzQBMj22aeuNsxfUTaIjS1qBJkozF3XRS9HBrkczFsGJVwd9vMEcqMazFfLhhIF9vO2Hd%2B5T05n4GAVJJIoEQAmhZ%2BujFl4lYxSH6KYXmY%2Fb4y%2BfevBmIVDEIqiRFTw8%2FGrMQMnIFLuo9iwzg%2FCnz%2B%2F7RnW7YFIACWSwASRm%2BGqXLZAoIASthaPHprojwbh7Xh%2Fkr3NtlrUMsC40UwjVuW1DH%2BVlkaty36exd9uDKn9OUStyKPmQBN6VbbgrxIToybSf5rle0JHrV%2F5iJrQ%2FZtsT1bgbyJTRU1lVd6OdoV23kdc2dnoqkRNa3xETebSUNRjNdvrGcaFoCZ%2BFBsVP6ImNXhRHmUVYKVnWiYyarozVgemioRrQ9U2wA775BxMOr%2Bj5gimCk34kELCnaFqDWCdfXJER80eTLIhvokh4dZQwt%2BJ7jm%2FvoRR40PkG3R%2F6ZXtPV5McrbXZqXcOz1aEUdtGONDiNQHKHXPdo97WQPOStSGJeUCcw%2BzSPz3aEXgt2atBVzHO82W9NpgCX8ATpiGKKaCDh37%2FjIwdQ2F9B8HTx0s4Tvg%2Bz5EyKnjuyFvWzevTxH7Q7DEh0yyYx6C0%2BrAxKYJ7PHGyh%2B1AKDUR8bm5UOYefnjX9tN3J9Y1ztpAiSRlgCmNkKz8ZsxO0cAXT%2BS9CIwOSpq1r3wC4NkawATIaJm3TM7i3Uk%2Bbt8VVzyqFl38H5h0FLAVIaSqFn3fNDmDfUgqV8CJiOJGu14pQNTq42QZG8CE5JEjXIKXVCQQ1oQmKZN%2Fa5xU%2FkgpKWBSapHbQPUtF1IGpT5pqhH7QgUVYZIcrZ4U5Sj1ttvgZo00vxN6KZ1ZO6UotZ7NnvYbwMhjLSBxza7qJ0AoelEwqyjVgdCaYAEMmrqykBJ4VRuZpH3DpACOIXB6wwGWQNaw4YT9dOblq21YJJiH0maP1GDxUigzMgdy9VhcTo%2B%2FG3ojqbLsGh1jRhisQp95Ma%2BWK4Gy1T0DLQlDPEv1X2Xr4VYWO8AAAAASUVORK5CYII%3D)
![Modrinth Downloads](https://img.shields.io/modrinth/dt/6zIy0zBK?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iNTEyIiBoZWlnaHQ9IjUxNCIgdmlld0JveD0iMCAwIDUxMiA1MTQiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI%2BCiAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik01MDMuMTYgMzIzLjU2QzUxNC41NSAyODEuNDcgNTE1LjMyIDIzNS45MSA1MDMuMiAxOTAuNzZDNDY2LjU3IDU0LjIyOTkgMzI2LjA0IC0yNi44MDAxIDE4OS4zMyA5Ljc3OTkxQzgzLjgxMDEgMzguMDE5OSAxMS4zODk5IDEyOC4wNyAwLjY4OTk0MSAyMzAuNDdINDMuOTlDNTQuMjkgMTQ3LjMzIDExMy43NCA3NC43Mjk4IDE5OS43NSA1MS43MDk4QzMwNi4wNSAyMy4yNTk4IDQxNS4xMyA4MC42Njk5IDQ1My4xNyAxODEuMzhMNDExLjAzIDE5Mi42NUMzOTEuNjQgMTQ1LjggMzUyLjU3IDExMS40NSAzMDYuMyA5Ni44MTk4TDI5OC41NiAxNDAuNjZDMzM1LjA5IDE1NC4xMyAzNjQuNzIgMTg0LjUgMzc1LjU2IDIyNC45MUMzOTEuMzYgMjgzLjggMzYxLjk0IDM0NC4xNCAzMDguNTYgMzY5LjE3TDMyMC4wOSA0MTIuMTZDMzkwLjI1IDM4My4yMSA0MzIuNCAzMTAuMyA0MjIuNDMgMjM1LjE0TDQ2NC40MSAyMjMuOTFDNDY4LjkxIDI1Mi42MiA0NjcuMzUgMjgxLjE2IDQ2MC41NSAzMDguMDdMNTAzLjE2IDMyMy41NloiIGZpbGw9IiMxYmQ5NmEiLz4KICA8cGF0aCBkPSJNMzIxLjk5IDUwNC4yMkMxODUuMjcgNTQwLjggNDQuNzUwMSA0NTkuNzcgOC4xMTAxMSAzMjMuMjRDMy44NDAxMSAzMDcuMzEgMS4xNyAyOTEuMzMgMCAyNzUuNDZINDMuMjdDNDQuMzYgMjg3LjM3IDQ2LjQ2OTkgMjk5LjM1IDQ5LjY3OTkgMzExLjI5QzUzLjAzOTkgMzIzLjggNTcuNDUgMzM1Ljc1IDYyLjc5IDM0Ny4wN0wxMDEuMzggMzIzLjkyQzk4LjEyOTkgMzE2LjQyIDk1LjM5IDMwOC42IDkzLjIxIDMwMC40N0M2OS4xNyAyMTAuODcgMTIyLjQxIDExOC43NyAyMTIuMTMgOTQuNzYwMUMyMjkuMTMgOTAuMjEwMSAyNDYuMjMgODguNDQwMSAyNjIuOTMgODkuMTUwMUwyNTUuMTkgMTMzQzI0NC43MyAxMzMuMDUgMjM0LjExIDEzNC40MiAyMjMuNTMgMTM3LjI1QzE1Ny4zMSAxNTQuOTggMTE4LjAxIDIyMi45NSAxMzUuNzUgMjg5LjA5QzEzNi44NSAyOTMuMTYgMTM4LjEzIDI5Ny4xMyAxMzkuNTkgMzAwLjk5TDE4OC45NCAyNzEuMzhMMTc0LjA3IDIzMS45NUwyMjAuNjcgMTg0LjA4TDI3OS41NyAxNzEuMzlMMjk2LjYyIDE5Mi4zOEwyNjkuNDcgMjE5Ljg4TDI0NS43OSAyMjcuMzNMMjI4Ljg3IDI0NC43MkwyMzcuMTYgMjY3Ljc5QzIzNy4xNiAyNjcuNzkgMjUzLjk1IDI4NS42MyAyNTMuOTggMjg1LjY0TDI3Ny43IDI3OS4zM0wyOTQuNTggMjYwLjc5TDMzMS40NCAyNDkuMTJMMzQyLjQyIDI3My44MkwzMDQuMzkgMzIwLjQ1TDI0MC42NiAzNDAuNjNMMjEyLjA4IDMwOC44MUwxNjIuMjYgMzM4LjdDMTg3LjggMzY3Ljc4IDIyNi4yIDM4My45MyAyNjYuMDEgMzgwLjU2TDI3Ny41NCA0MjMuNTVDMjE4LjEzIDQzMS40MSAxNjAuMSA0MDYuODIgMTI0LjA1IDM2MS42NEw4NS42Mzk5IDM4NC42OEMxMzYuMjUgNDUxLjE3IDIyMy44NCA0ODQuMTEgMzA5LjYxIDQ2MS4xNkMzNzEuMzUgNDQ0LjY0IDQxOS40IDQwMi41NiA0NDUuNDIgMzQ5LjM4TDQ4OC4wNiAzNjQuODhDNDU3LjE3IDQzMS4xNiAzOTguMjIgNDgzLjgyIDMyMS45OSA1MDQuMjJaIiBmaWxsPSIjMWJkOTZhIi8%2BCjwvc3ZnPg%3D%3D)
[![Proxy Stats](https://img.shields.io/bstats/servers/13699?logo=minecraft&label=Servers)](https://bstats.org/plugin/velocity/LimboFilter/13699)
[![Proxy Stats](https://img.shields.io/bstats/players/13699?logo=minecraft&label=Players)](https://bstats.org/plugin/velocity/LimboFilter/13699)

Most powerful bot filtering solution for Minecraft proxies. Built with LimboAPI. \
[Modrinth](https://modrinth.com/plugin/limbofilter) \
[Описание и обсуждение на русском языке (spigotmc.ru)](https://spigotmc.ru/resources/limboapi-limboauth-limbofilter-virtualnye-servera-dlja-velocity.715/) \
[Описание и обсуждение на русском языке (rubukkit.org)](http://rubukkit.org/threads/limboapi-limboauth-limbofilter-virtualnye-servera-dlja-velocity.177904/)

Test server: [``ely.su``](https://hotmc.ru/minecraft-server-203216)

## See also

- [LimboAuth](https://github.com/Elytrium/LimboAuth) - Auth System built in virtual server (Limbo). Uses [BCrypt](https://en.wikipedia.org/wiki/Bcrypt), has [TOTP](https://en.wikipedia.org/wiki/Time-based_one-time_password) [2FA](https://en.wikipedia.org/wiki/Help:Two-factor_authentication) feature. Supports literally any database due to [OrmLite](https://ormlite.com).
- [LimboAPI](https://github.com/Elytrium/LimboAPI) - Library for sending players to virtual servers (called limbo)

## Features of LimboFilter

- Highly customizable [CAPTCHA's](https://en.wikipedia.org/wiki/CAPTCHA) - change fonts, backplates, colors, alphabet-pattern, length;
- Client settings and [brand](https://wiki.vg/Plugin_channels#minecraft:brand) checking;
- Highly customisable config - you can change all the messages the plugin sends;
- Ability to partially disable protection on low-loads of [proxy](https://en.wikipedia.org/wiki/Proxy_server);
- Ability to prepare [raw packets](https://en.wikipedia.org/wiki/Network_packet) to reduce [CPU](https://en.wikipedia.org/wiki/Central_processing_unit) usage;
- Fast [MCEdit](https://www.mcedit.net/about.html)/[StructureBlock](https://minecraft.fandom.com/wiki/Structure_Block) schematic world loading for [CAPTCHA](https://en.wikipedia.org/wiki/CAPTCHA) checking;
- And more...

## Commands and permissions

### Admin

- ***limbofilter.commands.sendfilter* | /sendfilter** - Send Player to Filter Command
- ***limbofilter.admin.stats* | /lfilter stats** - Plugin Statistics Command
- ***limbofilter.admin.reload* | /lfilter reload** - Reload Plugin Command
- ***limbofilter.admin.***\* - Gives All Admin Permissions

## LimboFilter /vs/ popular antibot solutions:

Test server: i7-3770 (4c/8t 3.4GHz) Dedicated server, Ubuntu Server 20.04, OpenJDK 11, 16GB DDR3 1600MHz RAM, 4GB RAM is allocated to proxy. \
Attack: Motd + Join bot attack (100k joins per seconds, 1.17 Protocol)

| Proxy server                            | Info                                        | Boot time | % CPU on attack |
|-----------------------------------------|---------------------------------------------|-----------|-----------------|
| Velocity                                | LimboFilter + LimboAuth Online/Offline Mode | 2 sec     | 20%             |
| Velocity                                | LimboFilter + Offline Mode                  | 2 sec     | 20%             |
| Leymooo's BungeeCord BotFilter          | JPremium Online/Offline Mode                | 8 sec     | 95%             |
| Leymooo's BungeeCord BotFilter          | Offline Mode                                | 8 sec     | 40%             |
| yooniks' BungeeCord Aegis Escanor 1.3.1 | Offline Mode                                | 10 sec    | 20%             |
| yooniks' BungeeCord Aegis 9.2.1         | Offline Mode                                | 10 sec    | 100% (xd)       |
| Velocity                                | JPremium Online/Offline Mode                | 2 sec     | 95%             |
| Velocity                                | BotSentry 9.2 + Online Mode                 | 2 sec     | 70%             |
| Velocity                                | Online Mode                                 | 2 sec     | 70%             |
| Velocity                                | Offline Mode                                | 2 sec     | 55%             |

## Donation

Your donations are really appreciated. Donations wallets/links/cards:

- MasterCard Debit Card (Tinkoff Bank): ``5536 9140 0599 1975``
- Qiwi Wallet: ``PFORG`` or [this link](https://my.qiwi.com/form/Petr-YSpyiLt9c6)
- YooMoney Wallet: ``4100 1721 8467 044`` or [this link](https://yoomoney.ru/quickpay/shop-widget?writer=seller&targets=Donation&targets-hint=&default-sum=&button-text=11&payment-type-choice=on&mobile-payment-type-choice=on&hint=&successURL=&quickpay=shop&account=410017218467044)
- Monero (XMR): 86VQyCz68ApebfFgrzRFAuYLdvd3qG8iT9RHcru9moQkJR9W2Q89Gt3ecFQcFu6wncGwGJsMS9E8Bfr9brztBNbX7Q2rfYS
