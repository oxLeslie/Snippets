# Snippets

#### kAnn
```
/** <#annotation#> */
```

#### kCBlock
```
[<#code#>];
```

#### kInit
```
[[<#Class#> alloc] init];
```

#### kGet
```
- (<#returnType#> *)<#property#> {
    if (!_<#property#>) {
        _<#property#> = [[<#returnType#> alloc] init];
    }
    return _<#property#>;
}
```

#### kIf
```
if (<#conditions#>) { <#code#>; }
```

#### kElse
```
else { <#code#>; }
```

#### kPro
```
@property (nonatomic, <#key#>) <#class#> *<#name#>;
```

#### kStrong
```
@strongify(<#obj#>);
```

#### kWeak
```
@weakify(<#obj#>);
```

#### kRetain
```
printf("retain count = %ld\n",CFGetRetainCount((__bridge CFTypeRef)(<#obj#>)));
```

#### kPSingle
```
#pragma mark - <#title#>
```

#### kPGroup
```
#pragma mark - Override
#pragma mark - Events
#pragma mark - Public
#pragma mark - Private
#pragma mark - Setter & Getter
```



