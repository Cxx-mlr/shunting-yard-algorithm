# Shunting Yard Algorithm

```cpp
#include "ShuntYard.hpp"

int main() {
    std::string input = {};

    while (std::cout << "\n> " && std::getline(std::cin, input)) {
        ShuntYard::compute(std::move(input));
    }
    return 0;
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
