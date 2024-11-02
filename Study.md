# Self-study
---
## Các cách để duyệt qua một container
![alt text](image-159.png)
![alt text](image-160.png)
![alt text](image-161.png)
![alt text](image-162.png)
![alt text](image-163.png)

## istringstream trong thư viện sstream
![alt text](image-164.png)
![alt text](image-165.png)
![alt text](image-166.png)
![alt text](image-167.png)
![alt text](image-168.png)
![alt text](image-169.png)

## Vectors
![alt text](image-345.png)
![alt text](image-344.png)
![alt text](image-346.png)
![alt text](image-347.png)
![alt text](image-348.png)
![alt text](image-349.png)
![alt text](image-350.png)
![alt text](image-351.png)
![alt text](image-352.png)
![alt text](image-353.png)
![alt text](image-354.png)
![alt text](image-355.png)
![alt text](image-356.png)
![alt text](image-357.png)
![alt text](image-358.png)
![alt text](image-359.png)
![alt text](image-360.png)
![alt text](image-361.png)

## *--recurse-submodules* trong git
![alt text](image-403.png)
![alt text](image-404.png)
![alt text](image-405.png)

## constexpr
constexpr là viết tắt của constant expression

## ifstream
![alt text](image-406.png)

## static function
![alt text](image-407.png)
![alt text](image-408.png)
![alt text](image-409.png)
![alt text](image-410.png)

## std::byte
![alt text](image-413.png)
![alt text](image-412.png)
![alt text](image-414.png)

## std::optional
![alt text](image-411.png)

## std::ios::ate
![alt text](image-416.png)
![alt text](image-417.png)
![alt text](image-418.png)

## tellg() and seek()
![alt text](image-421.png)
![alt text](image-422.png)
![alt text](image-423.png)
![alt text](image-424.png)

## ReadFile
```C++
static std::optional<std::vector<std::byte>> ReadFile(const std::string &path)
{   
    std::ifstream is{path, std::ios::binary | std::ios::ate};
    if( !is )
        return std::nullopt;
    
    auto size = is.tellg();
    std::vector<std::byte> contents(size);    
    
    is.seekg(0);
    is.read((char*)contents.data(), size);

    if( contents.empty() )
        return std::nullopt;
    return std::move(contents);
}
```
![alt text](image-415.png)
![alt text](image-419.png)
![alt text](image-420.png)
![alt text](image-425.png)
![alt text](image-426.png)
![alt text](image-427.png)
![alt text](image-428.png)
![alt text](image-429.png)

## main(int argc, const char **argv)
![alt text](image-430.png)
![alt text](image-431.png)
![alt text](image-432.png)
![alt text](image-433.png)
![alt text](image-434.png)

## std::string_view
![alt text](image-435.png)
![alt text](image-436.png)
![alt text](image-437.png)
![alt text](image-438.png)
![alt text](image-439.png)
![alt text](image-440.png)

## std::move
```C++
    if( osm_data.empty() && !osm_data_file.empty() ) {
        std::cout << "Reading OpenStreetMap data from the following file: " <<  osm_data_file << std::endl;
        auto data = ReadFile(osm_data_file);
        if( !data )
            std::cout << "Failed to read." << std::endl;
        else
            osm_data = std::move(*data);
    }
```
![alt text](image-441.png)

## #pragma once
![alt text](image-442.png)
![alt text](image-443.png)
![alt text](image-444.png)
![alt text](image-445.png)

## cstddef header file
![alt text](image-446.png)

## double m_MetricScale = 1.f;
![alt text](image-447.png)
![alt text](image-448.png)

## auto &Railways() const noexcept { return m_Railways; }
![alt text](image-449.png)
![alt text](image-450.png)
nd là viết tắt của nano degree

## get user input và trả ra ngoài
![alt text](image-451.png)
![alt text](image-452.png)

## Assert
![alt text](image-458.png)
![alt text](image-459.png)
![alt text](image-460.png)

## "struct" keyword trong C và C++
![alt text](image-461.png)
![alt text](image-462.png)
![alt text](image-463.png)

## Initializer list
![alt text](image-487.png)
![alt text](image-488.png)
![alt text](image-489.png)

## Derive là gì
![alt text](image-492.png)

## Không gọi constructor của base class ở initializer list thì sao?
![alt text](image-493.png)
![alt text](image-494.png)
![alt text](image-495.png)

## Catch ( ... )
![alt text](image-503.png)
![alt text](image-504.png)

## Deep copy and deep assigment
![alt text](image-624.png)
(*) Memory leak, dangling pointer

## Function pointer
![alt text](image-828.png)
```C++
#include <stdio.h>

// Khai báo một hàm đơn giản
int add(int a, int b) {
    return a + b;
}

int subtract(int a, int b) {
    return a - b;
}

int main() {
    // Khai báo một con trỏ hàm
    int (*operation)(int, int);

    // Gán hàm 'add' cho con trỏ hàm
    operation = &add;
    printf("Addition: %d\n", operation(5, 3));

    // Gán hàm 'subtract' cho con trỏ hàm
    operation = &subtract;
    printf("Subtraction: %d\n", operation(5, 3));

    return 0;
}
```
![alt text](image-829.png)

## Sudo apt
![alt text](image-830.png)

## std::stof
![alt text](image-831.png)
![alt text](image-832.png)

## std::replace
![alt text](image-833.png)
![alt text](image-834.png)
![alt text](image-835.png)

## .c_str()
![alt text](image-836.png)
![alt text](image-837.png)
![alt text](image-838.png)

## dirent.h
![alt text](image-839.png)