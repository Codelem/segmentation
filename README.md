# segmentation
Pin 里面使用的文本分词功能代码

# 使用方法
```objc
NSArray<NSString *> *texts = [@"测试中文分词功能" segmentation:PINSegmentationOptionsNone];
[texts enumerateObjectsUsingBlock:^(NSString * _Nonnull obj, NSUInteger idx, BOOL * _Nonnull stop) {
    NSLog(@"%@", obj);
}];
```
