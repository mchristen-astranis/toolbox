# Miscellaneous

`ostream <<` takes function pointers: https://en.cppreference.com/w/cpp/io/basic_ostream/operator_ltlt

so ...

```cpp
ostream& HelloWorld(ostream&) {
  ostream << "Hello World!";
}

std::cout << HelloWorld << std::endl;
```

totally works.

# Open Questions?

- maybe these should be snippets of code that can all be run? Is there a way to show the contents of another file in .md? Probably not, but maybe .rst?
