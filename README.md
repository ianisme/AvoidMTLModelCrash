# AvoidMTLModelCrash
Avoid some Mantle crash
```
#import "NSNumber+AvoidMTLModelCrash.h"
#import "NSString+AvoidMTLModelCrash.h"
int main(int argc, char * argv[])
{
    @autoreleasepool {
       [NSNumber avoidMTLModelCrash];
       return UIApplicationMain(argc, argv, nil, NSStringFromClass([AppDelegate class]));
    }
}
```
