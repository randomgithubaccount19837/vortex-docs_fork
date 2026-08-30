---
title: TweenService
description: A service that can be used to smoothly interpolate properties of instances.
---

<!-- 
TweenService

Copied and modified from the Roblox documentation
im kind of new to this markdown stuff idk
-->

## Summary

<details>
<summary><b>Methods</b></summary>
Methods of the `TweenService`.
<br><br>

* [Create](#create): `Tween`

</details>

## Methods
### Create
Creates a new `Tween` given the object whose properties are to be tweened, a `TweenInfo`, and a dictionary of goal property values.
```lua
TweenService:Create(
instance: Instance, tweenInfo: TweenInfo, propertyTable: Dictionary
): Tween
```
#### Parameters
##### instance: `Instance`
The `Instance` whose properties are to be tweened.
##### tweenInfo: `TweenInfo`
The `TweenInfo` to be used for the tween.
##### propertyTable: `Dictionary`
A dictionary of properties, and their target values, to be tweened.
#### Returns
`Tween`\
The newly created `Tween` configured to interpolate the given properties toward their target values. Call `TweenBase:Play()` on the returned object to start the tween.
