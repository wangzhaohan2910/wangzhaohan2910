<details>
<summary><h3>The information of me, wangzhaohan2910.</h3></summary>

- 👋 Hi, I’m @wangzhaohan2910
- 👀 I’m interested in OI.
- 🌱 I’m currently learning Graph Theory.
- 💞️ I’m looking to collaborate on Online Judges.
- ☎ How to reach me? My phone number is +86 15626067976.
- 📧 And, my email address is wangcf3000@sina.com
- 😄 Pronouns: He or Him ~in Minecraft~.
- ⚡ Fun fact: I AK IOI!
- ⌨ [My blog of Github](//wangzhaohan2910.github.io)
- 📖 [My blog of Word Press (Infinity Free)](http://wangzhaohan2910.free.nf)
- 📷 [My gallery (Infinity Free)](http://wangzhaohan2910.000.pe)
- ✌️ [My BB (Infinity Free)](http://wangzhaohan2910.kesug.com)
- 💻 [My luogu-dev account (commonly used)](//www.luogu.com.cn/user/629944)
- 💻 [My luogu-dev account (not commonly used)](//www.luogu.com.cn/user/1418972)
- 💻 [My gitee account](//gitee.com/wangzhaohan2910)
- 💻 [My sourceforge account](//sourceforge.net/u/wangzhaohan2910/profile)
- ![](https://badges.toozhao.com/badges/01J66YFE2G7TRVFS17Z8FFMQ7X/green.svg)
<!---
wangzhaohan2910/wangzhaohan2910 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
</details>
<details>
<summary><h3>My Template of C++ in VSCode:</h3></summary>
```json
{
    "FRFW": {
        "prefix": "frfw",
        "body": [
            "char buf[${0:1 << 20}], *p1, *p2;",
            "#define getchar() (p1 == p2 && (p2 = (p1 = buf) + fread(buf, 1, ${0:1 << 20}, stdin), p1 == p2) ? EOF : *p1++)",
            "inline void read(int &x)",
            "{",
            "    register int f = 1;",
            "    register char ch = getchar();",
            "    x ^= x;",
            "    while (ch < 48 || ch > 57)",
            "    {",
            "        if (ch == '-')",
            "            f = -1;",
            "        ch = getchar();",
            "    }",
            "    while (ch > 47 && ch < 58)",
            "        x = x * 10 + (ch ^ 48), ch = getchar();",
            "    x *= f;",
            "}",
            "char obuf[${0:1 << 20}], *p3 = obuf;",
            "#define putchar(x) (p3 - obuf < ${0:1 << 20}) ? (*p3++ = x) : (fwrite(obuf, p3 - obuf, 1, stdout), p3 = obuf, *p3++ = x)",
            "inline void write(int &x)",
            "{",
            "    if (!x)",
            "    {",
            "        putchar('0');",
            "        return;",
            "    }",
            "    static int c[20];",
            "    register int len{}, k1{x};",
            "    if (k1 < 0)",
            "        k1 = -k1, putchar('-');",
            "    while (k1)",
            "        c[len++] = k1 % 10 ^ 48, k1 /= 10;",
            "    while (len--)",
            "        putchar(c[len]);",
            "}",
            "struct _FAST_",
            "{",
            "    ~_FAST_()",
            "    {",
            "        fwrite(obuf, p3 - obuf, 1, stdout);",
            "    }",
            "} _fast_;"
        ],
        "description": "Fast Read Fast Write Template"
    },
    "LG": {
        "prefix": "lg",
        "body": [
            "#include <bits/extc++.h>",
            "${0:// }#define int long long",
            "using namespace std;",
            "using namespace __gnu_pbds;",
            "signed main()",
            "{",
            "    return 0;",
            "}"
        ],
        "description": "Luogu Template"
    },
    "CF": {
        "prefix": "cf",
        "body": [
            "#include <bits/stdc++.h>",
            "${0:// }#define int long long",
            "using namespace std;",
            "signed main()",
            "{",
            "    return 0;",
            "}"
        ],
        "description": "CodeForces Template"
    },
    "VS": {
        "prefix": "vs",
        "body": [
            "#define _CRT_SECURE_NO_WARNINGS",
            "#include <any>",
            "#include <bit>",
            "#include <ios>",
            "#include <map>",
            "#include <new>",
            "#include <set>",
            "#include <list>",
            "#include <span>",
            "#include <array>",
            "#include <cfenv>",
            "#include <cmath>",
            "#include <ctime>",
            "#include <deque>",
            "#include <latch>",
            "#include <mutex>",
            "#include <queue>",
            "#include <ratio>",
            "#include <regex>",
            "#include <stack>",
            "#include <tuple>",
            "#include <atomic>",
            "#include <bitset>",
            "#include <cctype>",
            "#include <cerrno>",
            "#include <cfloat>",
            "#include <chrono>",
            "#include <cstdio>",
            "#include <cuchar>",
            "#include <cwchar>",
            "#include <format>",
            "#include <future>",
            "#include <iosfwd>",
            "#include <limits>",
            "#include <locale>",
            "#include <memory>",
            "#include <random>",
            "#include <ranges>",
            "#include <string>",
            "#include <thread>",
            "#include <vector>",
            "#include <barrier>",
            "#include <cassert>",
            "#include <ciso646>",
            "#include <climits>",
            "#include <clocale>",
            "#include <codecvt>",
            "#include <compare>",
            "#include <complex>",
            "#include <csetjmp>",
            "#include <csignal>",
            "#include <cstdarg>",
            "#include <cstddef>",
            "#include <cstdint>",
            "#include <cstdlib>",
            "#include <cstring>",
            "#include <ctgmath>",
            "#include <cwctype>",
            "#include <fstream>",
            "#include <iomanip>",
            "#include <istream>",
            "#include <numbers>",
            "#include <numeric>",
            "#include <ostream>",
            "#include <sstream>",
            "#include <utility>",
            "#include <variant>",
            "#include <version>",
            "#include <ccomplex>",
            "#include <charconv>",
            "#include <concepts>",
            "#include <cstdbool>",
            "#include <expected>",
            "#include <iostream>",
            "#include <iterator>",
            "#include <optional>",
            "#include <stdfloat>",
            "#include <typeinfo>",
            "#include <valarray>",
            "#include <algorithm>",
            "#include <cinttypes>",
            "#include <coroutine>",
            "#include <cstdalign>",
            "#include <exception>",
            "#include <semaphore>",
            "#include <stdexcept>",
            "#include <streambuf>",
            "#include <typeindex>",
            "#include <filesystem>",
            "#include <functional>",
            "#include <spanstream>",
            "#include <stacktrace>",
            "#include <stop_token>",
            "#include <syncstream>",
            "#include <stdatomic.h>",
            "#include <string_view>",
            "#include <type_traits>",
            "#include <forward_list>",
            "#include <shared_mutex>",
            "#include <system_error>",
            "#include <unordered_map>",
            "#include <unordered_set>",
            "#include <memory_resource>",
            "#include <source_location>",
            "#include <initializer_list>",
            "#include <scoped_allocator>",
            "#include <condition_variable>",
            "${0:// }#define int long long",
            "using namespace std;",
            "signed main()",
            "{",
            "    return 0;",
            "}"
        ],
        "description": "Visual Studio Template"
    }
}
```
</details>
