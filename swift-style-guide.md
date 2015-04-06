# Hyper Swift Style Guide

This style guide outlines the coding conventions of the iOS team at Hyper.

## Introduction

Other styles:  
https://github.com/raywenderlich/swift-style-guide#use-of-self


## Table of Contents

Add TOC

## Don't use self when not neccessary

**Preffered**  
```swift
data = [Int]()
```

**Not Preffered**  
```swift
self.data = [Int]()
 ```
 
## Don't speciofy Double numbers `.0` when not neccesary

**Preffered**  
```swift
CGRectMake(0, 0, 150, 40))
```

**Not Preffered**   
```swift
CGRectMake(0.0, 0.0, 150.0, 40.0))
```

##Selector

**Preffered**  
```swift
"readOnly:"
```

**Not Preffered**  
```swift
NSSelectorFromString("readOnly:")
```

## Use extensions to separate code sections instead for #paragma marks




##Lazy properites