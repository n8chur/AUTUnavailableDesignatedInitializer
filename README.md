A convenient macro to reduce boilerplate when opting out of designated initializers.

### `Header.h`
```objc
- (instancetype)initWithCoder:(NSCoder *)aDecoder NS_UNAVAILABLE;
```

### `Implementation.m`
```objc
- (instancetype)initWithCoder:(NSCoder *)aDecoder AUT_UNAVAILABLE_DESIGNATED_INITIALIZER;
```
