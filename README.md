# theme-test

```c++
std::map<std::string,int> m = {{"one",1},{"two",2},{"three",3}};
json j(m);
std::cout << j << std::endl;
```
Output:
```json
{"one":1,"three":3,"two":2}
```
