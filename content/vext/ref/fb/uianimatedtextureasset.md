---
title: UIAnimatedTextureAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[UIAnimatedTextureAsset](#constructor-0)**() |
| **[UIAnimatedTextureAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[UIAnimatedTextureAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[UIAnimatedTextureAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "frameRate" >}} | float |
| {{< prop "textureAtlas" >}} | [TextureAsset](/vext/ref/fb/textureasset) \| nil |
| {{< prop "textureInfos" >}} | [UITextureAtlasInfo](/vext/ref/fb/uitextureatlasinfo)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "UIAnimatedTextureAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### UIAnimatedTextureAsset {#constructor-0}

> **UIAnimatedTextureAsset**()

Creates a new [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset) frostbite instance.

### UIAnimatedTextureAsset {#constructor-1}

> **UIAnimatedTextureAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### UIAnimatedTextureAsset {#constructor-2}

> **UIAnimatedTextureAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset). |

### UIAnimatedTextureAsset {#constructor-3}

> **UIAnimatedTextureAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset). |

## Properties

### {{% prop-heading "frameRate" %}}

> **float**

### {{% prop-heading "textureAtlas" %}}

> **[TextureAsset](/vext/ref/fb/textureasset)** \| **nil**

### {{% prop-heading "textureInfos" %}}

> **[UITextureAtlasInfo](/vext/ref/fb/uitextureatlasinfo)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [UIAnimatedTextureAsset](/vext/ref/fb/uianimatedtextureasset) type.

