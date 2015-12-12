# iOS-Development-Best-Practices

Xcode plug-ins install http://alcatraz.io/ then
- XcodeColors [Github](https://github.com/robbiehanson/XcodeColors)
- KSImageNamed [Github](https://github.com/ksuther/KSImageNamed-Xcode)
- Lin [Github](https://github.com/questbeat/Lin)
- IconMaker [Github](https://github.com/kaphacius/IconMaker)
- Extractor Localizable Strings [Github](https://github.com/viniciusmo/extract-localizable-string-plugin-xcode)
- DerivedData Exterminator [Github](https://github.com/kattrali/deriveddata-exterminator)
- BBUFullIssueNavigator [Github](https://github.com/neonichu/BBUFullIssueNavigator)
- BBUDebuggerTuckAway [Github](https://github.com/neonichu/BBUDebuggerTuckAway)
- Backlight [Github](https://github.com/limejelly/Backlight-for-XCode)
- HighlightSelectedString [Github](https://github.com/keepyounger/HighlightSelectedString)

## Code
- Prefer ```let``` over ```var```  
declare let by default, change to var when needed.
- Return function early using ```guard``` [Why guard better than if?](http://natashatherobot.com/swift-guard-better-than-if/)
- **Don't force-unwrapping** Don't get value with ```foo!.function()``` instead use
```
if let foo = foo {  
}```   
or  
```
foo?.callFooBar()```
- Explicit optional declare use ```let foo:FooType?``` instead of ```let foo:FooType!``` if ```foo``` may be nil
- Only refer to ```self``` when required
