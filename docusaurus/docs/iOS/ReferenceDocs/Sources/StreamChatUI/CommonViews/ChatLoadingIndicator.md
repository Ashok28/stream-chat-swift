---
id: chatloadingindicator 
title: ChatLoadingIndicator
slug: /ReferenceDocs/Sources/StreamChatUI/CommonViews/chatloadingindicator
---

``` swift
open class ChatLoadingIndicator: _View, AppearanceProvider 
```

## Inheritance

[`_View`](_View), [`AppearanceProvider`](../Utils/AppearanceProvider)

## Properties

### `isHidden`

``` swift
override open var isHidden: Bool 
```

### `rotationPeriod`

``` swift
open var rotationPeriod: TimeInterval = 1
```

### `imageView`

``` swift
public private(set) lazy var imageView = UIImageView()
        .withoutAutoresizingMaskConstraints
```

## Methods

### `setUpAppearance()`

``` swift
override open func setUpAppearance() 
```

### `setUpLayout()`

``` swift
override open func setUpLayout() 
```

### `updateContent()`

``` swift
override open func updateContent() 
```

### `startRotation()`

``` swift
open func startRotation() 
```

### `stopRotating()`

``` swift
open func stopRotating() 
```